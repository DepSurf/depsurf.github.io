# Function: <code>keyctl_pkey_params_get</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583070016,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:82",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583070016,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583254784,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583254784,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583360640,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583360640,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583696768,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583696768,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583818064,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583818064,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583842048,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842048,
      "name": "keyctl_pkey_params_get",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584205008,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205008,
      "name": "keyctl_pkey_params_get",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584807536,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584807536,
      "name": "keyctl_pkey_params_get",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585505936,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585505936,
      "name": "keyctl_pkey_params_get",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585737568,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585737568,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585984816,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585984816,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495107024,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495107024,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228497548,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228497548,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289010944,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289010944,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274364520,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274364520,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583329376,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329376,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583266480,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583266480,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583313152,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583313152,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
```

```json
{
  "name": "keyctl_pkey_params_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583408176,
      "name": "keyctl_pkey_params_get",
      "external": false,
      "loc": "security/keys/keyctl_pkey.c:78",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583408176,
      "name": "keyctl_pkey_params_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int keyctl_pkey_params_get(key_serial_t id, const char * _info, struct kernel_pkey_params * params)
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
