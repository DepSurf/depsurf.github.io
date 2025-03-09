# Function: <code>ext4_xattr_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581854080,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:1199",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set",
        "fs/ext4/crypto_policy.c:ext4_process_policy",
        "fs/ext4/crypto_policy.c:ext4_inherit_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581854080,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582049904,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:1288",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582049904,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582139312,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:1289",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139312,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582245088,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2428",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245088,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582394048,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2464",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582394048,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582584400,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2480",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584400,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582685776,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2479",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582685776,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582859216,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2480",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582859216,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582963376,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2480",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582963376,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583278816,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2467",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set",
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583278816,
      "name": "ext4_xattr_set",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583380048,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2473",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set",
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583380048,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583402672,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2473",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set",
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583402672,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583747008,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2456",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set",
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583747008,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584304016,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2471",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set",
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584304016,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584952528,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2491",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set",
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584952528,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585180736,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2534",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set",
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585180736,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585413632,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2534",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set",
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585413632,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494637880,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2480",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494637880,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228082972,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2480",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228082972,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288449216,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2480",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288449216,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274008174,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2480",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274008174,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582932112,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2480",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582932112,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582869264,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2480",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582869264,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582920720,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2480",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582920720,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int ext4_xattr_set(struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583007776,
      "name": "ext4_xattr_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2480",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set",
        "fs/ext4/xattr_user.c:ext4_xattr_user_set",
        "fs/ext4/xattr_security.c:ext4_xattr_security_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583007776,
      "name": "ext4_xattr_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
