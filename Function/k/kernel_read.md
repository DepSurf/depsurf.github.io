# Function: <code>kernel_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kernel_read(struct file * file, loff_t offset, char * addr, long unsigned int count)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581017696,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/exec.c:829",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_intvec",
        "kernel/sysctl_binary.c:bin_ulongvec",
        "kernel/sysctl_binary.c:bin_dn_node_address",
        "kernel/kexec_file.c:copy_file_from_fd",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581017696,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int kernel_read(struct file * file, loff_t offset, char * addr, long unsigned int count)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581176128,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/exec.c:869",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_dn_node_address",
        "kernel/sysctl_binary.c:bin_ulongvec",
        "kernel/sysctl_binary.c:bin_intvec",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176128,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int kernel_read(struct file * file, loff_t offset, char * addr, long unsigned int count)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581253104,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/exec.c:874",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_dn_node_address",
        "kernel/sysctl_binary.c:bin_ulongvec",
        "kernel/sysctl_binary.c:bin_intvec",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253104,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int kernel_read(struct file * file, loff_t offset, char * addr, long unsigned int count)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581302544,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/exec.c:900",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_dn_node_address",
        "kernel/sysctl_binary.c:bin_ulongvec",
        "kernel/sysctl_binary.c:bin_intvec",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302544,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416800,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:418",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_dn_node_address",
        "kernel/sysctl_binary.c:bin_ulongvec",
        "kernel/sysctl_binary.c:bin_intvec",
        "fs/exec.c:prepare_binprm",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416800,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581575856,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:423",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:prepare_binprm",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575856,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581661616,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:423",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:prepare_binprm",
        "fs/exec.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661616,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581779504,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:432",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:prepare_binprm",
        "fs/exec.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581779504,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581851728,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:432",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:prepare_binprm",
        "fs/exec.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581851728,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582076464,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:450",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:search_binary_handler",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582076464,
      "name": "kernel_read",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582122416,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:465",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:search_binary_handler",
        "fs/kernel_read_file.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582122416,
      "name": "kernel_read",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582145456,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:465",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:search_binary_handler",
        "fs/kernel_read_file.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145456,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582464048,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:454",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:search_binary_handler",
        "fs/kernel_read_file.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582464048,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981648,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:451",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:search_binary_handler",
        "fs/kernel_read_file.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582981648,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583539568,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:439",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:search_binary_handler",
        "fs/kernel_read_file.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583539568,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583755376,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:439",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:search_binary_handler",
        "fs/kernel_read_file.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583755376,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583957968,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:445",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:search_binary_handler",
        "fs/kernel_read_file.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957968,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493318720,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:432",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:prepare_binprm",
        "fs/exec.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493318720,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226914984,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:432",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:prepare_binprm",
        "fs/exec.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary",
        "fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary",
        "fs/binfmt_elf_fdpic.c:elf_fdpic_fetch_phdrs",
        "fs/binfmt_flat.c:load_flat_shared_library",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226914984,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286858496,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:432",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:prepare_binprm",
        "fs/exec.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286858496,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273052674,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:432",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:prepare_binprm",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/binfmt_flat.c:load_flat_shared_library",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273052674,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581820464,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:432",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_dn_node_address",
        "kernel/sysctl_binary.c:bin_ulongvec",
        "kernel/sysctl_binary.c:bin_intvec",
        "fs/exec.c:prepare_binprm",
        "fs/exec.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820464,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758128,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:432",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:bin_dn_node_address",
        "kernel/sysctl_binary.c:bin_ulongvec",
        "kernel/sysctl_binary.c:bin_intvec",
        "fs/exec.c:prepare_binprm",
        "fs/exec.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758128,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581811776,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:432",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:prepare_binprm",
        "fs/exec.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811776,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
ssize_t kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581880992,
      "name": "kernel_read",
      "external": true,
      "loc": "fs/read_write.c:432",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:prepare_binprm",
        "fs/exec.c:kernel_read_file",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_phdrs",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_phdrs",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "security/keys/big_key.c:big_key_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880992,
      "name": "kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * buf</code>
</li>
<li>
<b>Param added. </b>
<code>loff_t * pos</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t offset</code>
</li>
<li>
<b>Param removed. </b>
<code>char * addr</code>
</li>
<li>
<b>Param reordered. </b>
<code>file, offset, addr, count</code> ➡️ <code>file, buf, count, pos</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int count</code> ➡️ <code>size_t count</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
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
