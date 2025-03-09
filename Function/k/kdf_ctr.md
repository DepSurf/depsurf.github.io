# Function: <code>kdf_ctr</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582605963,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:146",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582759428,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:146",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582959460,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:148",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583069006,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:148",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583253680,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:143",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583359499,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:143",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
int kdf_ctr(struct kdf_sdesc * sdesc, const u8 * src, unsigned int slen, u8 * dst, unsigned int dlen, unsigned int zlen)
```

```json
{
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583694208,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:143",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:keyctl_dh_compute_kdf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694208,
      "name": "kdf_ctr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
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
int kdf_ctr(struct kdf_sdesc * sdesc, const u8 * src, unsigned int slen, u8 * dst, unsigned int dlen, unsigned int zlen)
```

```json
{
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583815568,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:143",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:keyctl_dh_compute_kdf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583815568,
      "name": "kdf_ctr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
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
int kdf_ctr(struct kdf_sdesc * sdesc, const u8 * src, unsigned int slen, u8 * dst, unsigned int dlen, unsigned int zlen)
```

```json
{
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583839744,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:143",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:keyctl_dh_compute_kdf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583839744,
      "name": "kdf_ctr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int kdf_ctr(struct kdf_sdesc * sdesc, const u8 * src, unsigned int slen, u8 * dst, unsigned int dlen, unsigned int zlen)
```

```json
{
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584202704,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:143",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:keyctl_dh_compute_kdf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202704,
      "name": "kdf_ctr",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495104936,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:143",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:keyctl_dh_compute_kdf"
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
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228495136,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:143",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:keyctl_dh_compute_kdf"
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
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289009696,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:143",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274362666,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:143",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:keyctl_dh_compute_kdf"
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
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583328235,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:143",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583265339,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:143",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583312011,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:143",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
  "name": "kdf_ctr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583407035,
      "name": "kdf_ctr",
      "external": false,
      "loc": "security/keys/dh.c:143",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
int kdf_ctr(struct kdf_sdesc * sdesc, const u8 * src, unsigned int slen, u8 * dst, unsigned int dlen, unsigned int zlen)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int kdf_ctr(struct kdf_sdesc * sdesc, const u8 * src, unsigned int slen, u8 * dst, unsigned int dlen, unsigned int zlen)
```
</details>
</li>
</ul>
