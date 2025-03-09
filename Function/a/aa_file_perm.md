# Function: <code>aa_file_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582549680,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:598",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:match_file",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582549680,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1071
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582790208,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:595",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790208,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 997
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582885712,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:600",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582885712,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1133
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582955648,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:607",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582955648,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 922
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583117760,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:601",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583117760,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 922
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323456,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:601",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323456,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583441968,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:602",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583441968,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583627008,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:598",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583627008,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 890
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583733184,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:598",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733184,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 890
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request, bool in_atomic)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584116736,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:609",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584116736,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request, bool in_atomic)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584235760,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:598",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584235760,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request, bool in_atomic)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584260832,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:600",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584260832,
      "name": "aa_file_perm",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request, bool in_atomic)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584646784,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:600",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584646784,
      "name": "aa_file_perm",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request, bool in_atomic)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585303696,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:616",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585303696,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 721
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
int aa_file_perm(const char * op, const struct cred * subj_cred, struct aa_label * label, struct file * file, u32 request, bool in_atomic)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043152,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:761",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043152,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 742
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
int aa_file_perm(const char * op, const struct cred * subj_cred, struct aa_label * label, struct file * file, u32 request, bool in_atomic)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586278176,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:781",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586278176,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
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
int aa_file_perm(const char * op, const struct cred * subj_cred, struct aa_label * label, struct file * file, u32 request, bool in_atomic)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586535040,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:801",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_lock",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_permission",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/lsm.c:apparmor_file_receive",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586535040,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495529856,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:598",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495529856,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 944
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228896256,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:598",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228896256,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289610448,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:598",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289610448,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1256
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274706530,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:598",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274706530,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583701920,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:598",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583701920,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 890
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583638976,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:598",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583638976,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 890
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583685696,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:598",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583685696,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 890
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
int aa_file_perm(const char * op, struct aa_label * label, struct file * file, u32 request)
```

```json
{
  "name": "aa_file_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583785472,
      "name": "aa_file_perm",
      "external": true,
      "loc": "security/apparmor/file.c:598",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/lsm.c:common_file_perm",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:match_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583785472,
      "name": "aa_file_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool in_atomic</code>
</li>
</ul>
</details>
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
<code>op, label, file, request, in_atomic</code> ➡️ <code>op, subj_cred, label, file, request, in_atomic</code>
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
