# Function: <code>posix_acl_fix_xattr_userns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391776,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:598",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391776,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570064,
      "name": "posix_acl_fix_xattr_userns",
      "external": true,
      "loc": "fs/posix_acl.c:632",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user",
        "fs/fuse/dir.c:fuse_getxattr",
        "fs/fuse/dir.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570064,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581654832,
      "name": "posix_acl_fix_xattr_userns",
      "external": true,
      "loc": "fs/posix_acl.c:664",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654832,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581709216,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:665",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581709216,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581854864,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:665",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581854864,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035424,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:665",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035424,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123552,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:665",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123552,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582285536,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:666",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285536,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582384512,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:666",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582384512,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669760,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:669",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669760,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582738688,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:669",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582738688,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, struct user_namespace * mnt_userns, void * value, size_t size, bool from_user)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582767104,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:698",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582767104,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, struct user_namespace * mnt_userns, void * value, size_t size, bool from_user)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583094208,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:709",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583094208,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, struct user_namespace * mnt_userns, void * value, size_t size, bool from_user)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583575424,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:713",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583575424,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493982632,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:666",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493982632,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227447260,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:666",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227447260,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287625472,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:666",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287625472,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273502168,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:666",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273502168,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582353248,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:666",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582353248,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582290960,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:666",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582290960,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582343728,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:666",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582343728,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, void * value, size_t size)
```

```json
{
  "name": "posix_acl_fix_xattr_userns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582423296,
      "name": "posix_acl_fix_xattr_userns",
      "external": false,
      "loc": "fs/posix_acl.c:666",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/posix_acl.c:posix_acl_fix_xattr_to_user",
        "fs/posix_acl.c:posix_acl_fix_xattr_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582423296,
      "name": "posix_acl_fix_xattr_userns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param added. </b>
<code>bool from_user</code>
</li>
<li>
<b>Param reordered. </b>
<code>to, from, value, size</code> ➡️ <code>to, from, mnt_userns, value, size, from_user</code>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace * to, struct user_namespace * from, struct user_namespace * mnt_userns, void * value, size_t size, bool from_user)
```
</details>
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
