# Function: <code>aa_unix_peer_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582594160,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:530",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582594160,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2621
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582837792,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:530",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582837792,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2676
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582933664,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:530",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582933664,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2779
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582984128,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:538",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582984128,
      "name": "aa_unix_peer_perm.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
    },
    {
      "addr": 18446744071582988240,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583148096,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:538",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583148096,
      "name": "aa_unix_peer_perm.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
    },
    {
      "addr": 18446744071583152560,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583357072,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583357072,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1973
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583475792,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583475792,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1985
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583660128,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583660128,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1978
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583766416,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583766416,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1978
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584157888,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157888,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584276240,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584276240,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584301632,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584301632,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584688064,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584688064,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585351104,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:564",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585351104,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
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
int aa_unix_peer_perm(const struct cred * subj_cred, struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586092272,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:583",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586092272,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int aa_unix_peer_perm(const struct cred * subj_cred, struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586327744,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:583",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586327744,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int aa_unix_peer_perm(const struct cred * subj_cred, struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586584496,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:583",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586584496,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495567032,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495567032,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1688
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228930460,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228930460,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289660480,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289660480,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2320
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274736522,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274736522,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583735152,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583735152,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1978
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672208,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672208,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1978
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583718928,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718928,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1978
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
int aa_unix_peer_perm(struct aa_label * label, const char * op, u32 request, struct sock * sk, struct sock * peer_sk, struct aa_label * peer_label)
```

```json
{
  "name": "aa_unix_peer_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583819456,
      "name": "aa_unix_peer_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:539",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_may_send",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819456,
      "name": "aa_unix_peer_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1978
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<code>label, op, request, sk, peer_sk, peer_label</code> ➡️ <code>subj_cred, label, op, request, sk, peer_sk, peer_label</code>
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
