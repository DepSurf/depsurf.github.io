# Function: <code>kdf_alloc</code>

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
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582604659,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:91",
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
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582758131,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:91",
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
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582958407,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:91",
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
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583067965,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:91",
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
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583252662,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:87",
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
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583358470,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:87",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int kdf_alloc(struct kdf_sdesc * * sdesc_ret, char * hashname)
```

```json
{
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:87",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583693824,
      "name": "kdf_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071583696506,
      "name": "kdf_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int kdf_alloc(struct kdf_sdesc * * sdesc_ret, char * hashname)
```

```json
{
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:87",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583815184,
      "name": "kdf_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071591361528,
      "name": "kdf_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int kdf_alloc(struct kdf_sdesc * * sdesc_ret, char * hashname)
```

```json
{
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:87",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583839360,
      "name": "kdf_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071591304351,
      "name": "kdf_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int kdf_alloc(struct kdf_sdesc * * sdesc_ret, char * hashname)
```

```json
{
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:87",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202352,
      "name": "kdf_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071592292112,
      "name": "kdf_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584805931,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:83",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585504315,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:83",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585735850,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:67",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585983098,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:67",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495105672,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:87",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228495972,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:87",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289008532,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:87",
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
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274363266,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:87",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583327206,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:87",
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
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583264310,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:87",
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
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583310982,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:87",
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
  "name": "kdf_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583406006,
      "name": "kdf_alloc",
      "external": false,
      "loc": "security/keys/dh.c:87",
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
int kdf_alloc(struct kdf_sdesc * * sdesc_ret, char * hashname)
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
int kdf_alloc(struct kdf_sdesc * * sdesc_ret, char * hashname)
```
</details>
</li>
</ul>
