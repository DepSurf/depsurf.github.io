# Function: <code>ext4_xattr_set_handle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852992,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:1083",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852992,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1078
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582048672,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:1165",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582048672,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1222
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582138144,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:1171",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138144,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1168
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582243584,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2245",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582243584,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1426
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582392544,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2281",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582392544,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1426
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582960,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2297",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582960,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1375
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582684304,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2294",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582684304,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1399
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582857744,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2295",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582857744,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582961904,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2295",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582961904,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583277216,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2282",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583277216,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1399
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583378352,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2286",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583378352,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1489
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583400928,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2286",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583400928,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1548
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583745248,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2269",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745248,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1563
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584302224,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2284",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs",
        "fs/ext4/crypto.c:ext4_set_context",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584302224,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1585
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584950704,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2303",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs",
        "fs/ext4/crypto.c:ext4_set_context",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584950704,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1598
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585178816,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2346",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs",
        "fs/ext4/crypto.c:ext4_set_context",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585178816,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1693
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585411696,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2346",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs",
        "fs/ext4/crypto.c:ext4_set_context",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585411696,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1705
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494636440,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2295",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494636440,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1316
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228081576,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2295",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228081576,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1332
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288447376,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2295",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288447376,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1772
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274006924,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2295",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274006924,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1166
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582930640,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2295",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582930640,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582867792,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2295",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582867792,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582919248,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2295",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582919248,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
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
int ext4_xattr_set_handle(handle_t * handle, struct inode * inode, int name_index, const char * name, const void * value, size_t value_len, int flags)
```

```json
{
  "name": "ext4_xattr_set_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583006304,
      "name": "ext4_xattr_set_handle",
      "external": true,
      "loc": "fs/ext4/xattr.c:2295",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ext4/xattr_security.c:ext4_initxattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583006304,
      "name": "ext4_xattr_set_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
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
