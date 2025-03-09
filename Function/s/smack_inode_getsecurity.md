# Function: <code>smack_inode_getsecurity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int smack_inode_getsecurity(const struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582387184,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1489",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_inode_getsecctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582387184,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582608848,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1493",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_inode_getsecctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582608848,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582700896,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1487",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_inode_getsecctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582700896,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582788208,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1432",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_inode_getsecctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582788208,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582940784,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1406",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_inode_getsecctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940784,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583141024,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1480",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583141024,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583257120,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1348",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583257120,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583444256,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1435",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444256,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583550160,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1435",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583550160,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583900944,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1423",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900944,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020992,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1423",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020992,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int smack_inode_getsecurity(struct user_namespace * mnt_userns, struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049776,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1408",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049776,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int smack_inode_getsecurity(struct user_namespace * mnt_userns, struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584421376,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1408",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584421376,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int smack_inode_getsecurity(struct user_namespace * mnt_userns, struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585049968,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1414",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585049968,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int smack_inode_getsecurity(struct user_namespace * mnt_userns, struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585769936,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1474",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585769936,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int smack_inode_getsecurity(struct mnt_idmap * idmap, struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586001312,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1523",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586001312,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
int smack_inode_getsecurity(struct mnt_idmap * idmap, struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586248000,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1566",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586248000,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495323632,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1435",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495323632,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228700744,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1435",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228700744,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289318112,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1435",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289318112,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1296
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274538876,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1435",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274538876,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583518896,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1435",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583518896,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583455952,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1435",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583455952,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583502672,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1435",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583502672,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int smack_inode_getsecurity(struct inode * inode, const char * name, void * * buffer, bool alloc)
```

```json
{
  "name": "smack_inode_getsecurity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583599136,
      "name": "smack_inode_getsecurity",
      "external": false,
      "loc": "security/smack/smack_lsm.c:1435",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583599136,
      "name": "smack_inode_getsecurity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct inode * inode</code> ➡️ <code>struct inode * inode</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, name, buffer, alloc</code> ➡️ <code>mnt_userns, inode, name, buffer, alloc</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap * idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
</ul>
</details>
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
