# Function: <code>fscrypt_get_symlink</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581971584,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:214",
      "file": "fs/crypto/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971584,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582058640,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:214",
      "file": "fs/crypto/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582058640,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:233",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582220390,
      "name": "fscrypt_get_symlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071582219008,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582301056,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:233",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301056,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582586096,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:278",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582586096,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582657280,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:312",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582657280,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582686352,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:312",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582686352,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583012048,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:312",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583012048,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583482816,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:312",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583482816,
      "name": "fscrypt_get_symlink",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584077664,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:308",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584077664,
      "name": "fscrypt_get_symlink",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584304320,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:338",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584304320,
      "name": "fscrypt_get_symlink",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584521344,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:338",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584521344,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493877048,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:233",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493877048,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227359412,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:233",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227359412,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287510448,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:233",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287510448,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273440356,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:233",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273440356,
      "name": "fscrypt_get_symlink",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269792,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:233",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269792,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582207552,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:233",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207552,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582260272,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:233",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260272,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```

```json
{
  "name": "fscrypt_get_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582338864,
      "name": "fscrypt_get_symlink",
      "external": true,
      "loc": "fs/crypto/hooks.c:233",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582338864,
      "name": "fscrypt_get_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
const char * fscrypt_get_symlink(struct inode * inode, const void * caddr, unsigned int max_size, struct delayed_call * done)
```
</details>
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
