# Function: <code>aa_af_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582583760,
      "name": "aa_af_perm",
      "external": false,
      "loc": "security/apparmor/net.c:183",
      "file": "security/apparmor/net.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583760,
      "name": "aa_af_perm.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
  "name": "aa_af_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582826944,
      "name": "aa_af_perm",
      "external": false,
      "loc": "security/apparmor/net.c:183",
      "file": "security/apparmor/net.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582826944,
      "name": "aa_af_perm.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
  "name": "aa_af_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582922816,
      "name": "aa_af_perm",
      "external": false,
      "loc": "security/apparmor/net.c:183",
      "file": "security/apparmor/net.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922816,
      "name": "aa_af_perm.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980576,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:181",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980576,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583144448,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:181",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583144448,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583350368,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:201",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583350368,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583469024,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:201",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583469024,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583653424,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:197",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583653424,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583759712,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:197",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583759712,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584149968,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:198",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584149968,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584268304,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:200",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584268304,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584293552,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:200",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293552,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584679984,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:200",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679984,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585339664,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:200",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585339664,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int aa_af_perm(const struct cred * subj_cred, struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586080368,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:202",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586080368,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int aa_af_perm(const struct cred * subj_cred, struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586315680,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:202",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586315680,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int aa_af_perm(const struct cred * subj_cred, struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586572240,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:205",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586572240,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495559864,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:197",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495559864,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228923008,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:197",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228923008,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289650704,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:197",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289650704,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274730234,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:197",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274730234,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728448,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:197",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728448,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583665504,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:197",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583665504,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583712224,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:197",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712224,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```

```json
{
  "name": "aa_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583812720,
      "name": "aa_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:197",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583812720,
      "name": "aa_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int aa_af_perm(struct aa_label * label, const char * op, u32 request, u16 family, int type, int protocol)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred * subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>label, op, request, family, type, protocol</code> ➡️ <code>subj_cred, label, op, request, family, type, protocol</code>
</li>
</ul>
</details>
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
