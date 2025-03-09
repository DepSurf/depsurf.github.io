# Function: <code>fscrypt_limit_io_blocks</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u64 fscrypt_limit_io_blocks(const struct inode * inode, u64 lblk, u64 nr_blocks)
```

```json
{
  "name": "fscrypt_limit_io_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583505181,
      "name": "fscrypt_limit_io_blocks",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:467",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594020971,
      "name": "fscrypt_limit_io_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583505056,
      "name": "fscrypt_limit_io_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u64 fscrypt_limit_io_blocks(const struct inode * inode, u64 lblk, u64 nr_blocks)
```

```json
{
  "name": "fscrypt_limit_io_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584102157,
      "name": "fscrypt_limit_io_blocks",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:457",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596058950,
      "name": "fscrypt_limit_io_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584102032,
      "name": "fscrypt_limit_io_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u64 fscrypt_limit_io_blocks(const struct inode * inode, u64 lblk, u64 nr_blocks)
```

```json
{
  "name": "fscrypt_limit_io_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584329661,
      "name": "fscrypt_limit_io_blocks",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:457",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596582791,
      "name": "fscrypt_limit_io_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584329536,
      "name": "fscrypt_limit_io_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u64 fscrypt_limit_io_blocks(const struct inode * inode, u64 lblk, u64 nr_blocks)
```

```json
{
  "name": "fscrypt_limit_io_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584547549,
      "name": "fscrypt_limit_io_blocks",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:459",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597487185,
      "name": "fscrypt_limit_io_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584547424,
      "name": "fscrypt_limit_io_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
u64 fscrypt_limit_io_blocks(const struct inode * inode, u64 lblk, u64 nr_blocks)
```
</details>
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
