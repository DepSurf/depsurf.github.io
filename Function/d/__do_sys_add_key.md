# Function: <code>__do_sys_add_key</code>

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
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582937368,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:62",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
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
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583045912,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:62",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
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
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583228984,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:72",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
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
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583334888,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:72",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
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
long int __do_sys_add_key(const char * _type, const char * _description, const void * _payload, size_t plen, key_serial_t ringid)
```

```json
{
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583669024,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:74",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583669024,
      "name": "__do_sys_add_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
long int __do_sys_add_key(const char * _type, const char * _description, const void * _payload, size_t plen, key_serial_t ringid)
```

```json
{
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583790512,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:74",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583790512,
      "name": "__do_sys_add_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
long int __do_sys_add_key(const char * _type, const char * _description, const void * _payload, size_t plen, key_serial_t ringid)
```

```json
{
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583814688,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:74",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583814688,
      "name": "__do_sys_add_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
long int __do_sys_add_key(const char * _type, const char * _description, const void * _payload, size_t plen, key_serial_t ringid)
```

```json
{
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584177824,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:74",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584177824,
      "name": "__do_sys_add_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
long int __do_sys_add_key(const char * _type, const char * _description, const void * _payload, size_t plen, key_serial_t ringid)
```

```json
{
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777984,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:74",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777984,
      "name": "__do_sys_add_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
long int __do_sys_add_key(const char * _type, const char * _description, const void * _payload, size_t plen, key_serial_t ringid)
```

```json
{
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585474000,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:74",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474000,
      "name": "__do_sys_add_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
long int __do_sys_add_key(const char * _type, const char * _description, const void * _payload, size_t plen, key_serial_t ringid)
```

```json
{
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585705456,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:74",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585705456,
      "name": "__do_sys_add_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
long int __do_sys_add_key(const char * _type, const char * _description, const void * _payload, size_t plen, key_serial_t ringid)
```

```json
{
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585952496,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:74",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585952496,
      "name": "__do_sys_add_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495078820,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:72",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__arm64_sys_add_key"
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
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228473312,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:72",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__se_sys_add_key"
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
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288976516,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:72",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__se_sys_add_key"
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
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274344290,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:72",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__se_sys_add_key"
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
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583303624,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:72",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
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
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583240760,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:72",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
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
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583287656,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:72",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
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
  "name": "__do_sys_add_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583382264,
      "name": "__do_sys_add_key",
      "external": false,
      "loc": "security/keys/keyctl.c:72",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key"
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
long int __do_sys_add_key(const char * _type, const char * _description, const void * _payload, size_t plen, key_serial_t ringid)
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
