# Function: <code>__do_sys_request_key</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582936948,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:158",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
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
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583045492,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:158",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
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
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583228564,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:168",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
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
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583334468,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:168",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
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
long int __do_sys_request_key(const char * _type, const char * _description, const char * _callout_info, key_serial_t destringid)
```

```json
{
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583668512,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:167",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583668512,
      "name": "__do_sys_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
long int __do_sys_request_key(const char * _type, const char * _description, const char * _callout_info, key_serial_t destringid)
```

```json
{
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583790000,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:167",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583790000,
      "name": "__do_sys_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
long int __do_sys_request_key(const char * _type, const char * _description, const char * _callout_info, key_serial_t destringid)
```

```json
{
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583814160,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:167",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583814160,
      "name": "__do_sys_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
long int __do_sys_request_key(const char * _type, const char * _description, const char * _callout_info, key_serial_t destringid)
```

```json
{
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584177296,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:167",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584177296,
      "name": "__do_sys_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
long int __do_sys_request_key(const char * _type, const char * _description, const char * _callout_info, key_serial_t destringid)
```

```json
{
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777376,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:167",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777376,
      "name": "__do_sys_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
long int __do_sys_request_key(const char * _type, const char * _description, const char * _callout_info, key_serial_t destringid)
```

```json
{
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585474752,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:167",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474752,
      "name": "__do_sys_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
long int __do_sys_request_key(const char * _type, const char * _description, const char * _callout_info, key_serial_t destringid)
```

```json
{
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585706208,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:167",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585706208,
      "name": "__do_sys_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
long int __do_sys_request_key(const char * _type, const char * _description, const char * _callout_info, key_serial_t destringid)
```

```json
{
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585953248,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:167",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585953248,
      "name": "__do_sys_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495077988,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:168",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__arm64_sys_request_key"
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
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228473904,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:168",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__se_sys_request_key"
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
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288975976,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:168",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__se_sys_request_key"
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
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274344676,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:168",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__se_sys_request_key"
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
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583303204,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:168",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
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
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583240340,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:168",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
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
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583287236,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:168",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
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
  "name": "__do_sys_request_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583381844,
      "name": "__do_sys_request_key",
      "external": false,
      "loc": "security/keys/keyctl.c:168",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key"
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
long int __do_sys_request_key(const char * _type, const char * _description, const char * _callout_info, key_serial_t destringid)
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
