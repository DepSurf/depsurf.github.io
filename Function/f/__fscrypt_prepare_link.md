# Function: <code>__fscrypt_prepare_link</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581797328,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:51",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797328,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581971840,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971840,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582058896,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582058896,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582219936,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219936,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582301984,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301984,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582586688,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:54",
      "file": "fs/crypto/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582586688,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582656768,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:54",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582656768,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582685840,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:54",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582685840,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011536,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:54",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011536,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583482096,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:54",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583482096,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584076864,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076864,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584303520,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584303520,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584520544,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520544,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493877456,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493877456,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227359820,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227359820,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287512016,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287512016,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273441246,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273441246,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582270720,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270720,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582208480,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208480,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582261200,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261200,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "__fscrypt_prepare_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582339792,
      "name": "__fscrypt_prepare_link",
      "external": true,
      "loc": "fs/crypto/hooks.c:52",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582339792,
      "name": "__fscrypt_prepare_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __fscrypt_prepare_link(struct inode * inode, struct inode * dir)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dentry * dentry</code>
</li>
</ul>
</details>
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
