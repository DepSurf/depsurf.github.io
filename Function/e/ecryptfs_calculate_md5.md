# Function: <code>ecryptfs_calculate_md5</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ecryptfs_calculate_md5(char * dst, struct ecryptfs_crypt_stat * crypt_stat, char * src, int len)
```

```json
{
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582010848,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:87",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582010848,
      "name": "ecryptfs_calculate_md5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582224992,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:101",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224992,
      "name": "ecryptfs_calculate_md5.isra.15",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582314496,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:101",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582314496,
      "name": "ecryptfs_calculate_md5.isra.17",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582399152,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:101",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582399152,
      "name": "ecryptfs_calculate_md5.isra.18",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582550048,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:87",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582550048,
      "name": "ecryptfs_calculate_md5.isra.18",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:87",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582742144,
      "name": "ecryptfs_calculate_md5.isra.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071582751337,
      "name": "ecryptfs_calculate_md5.isra.20.cold.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582850071,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:87",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583024983,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:73",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583131191,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:73",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583452117,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:61",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583564709,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:61",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583587317,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:61",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583945493,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:61",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584527207,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:61",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585198711,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:61",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585427710,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:61",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585662382,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:61",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494840952,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:73",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228259632,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:73",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288689928,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:73",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274163194,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:73",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583099927,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:73",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583037079,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:73",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583088535,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:73",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
  "name": "ecryptfs_calculate_md5",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583177751,
      "name": "ecryptfs_calculate_md5",
      "external": false,
      "loc": "fs/ecryptfs/crypto.c:73",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int ecryptfs_calculate_md5(char * dst, struct ecryptfs_crypt_stat * crypt_stat, char * src, int len)
```
</details>
</li>
</ul>
