# Function: <code>kexec_image_post_load_cleanup_default</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580126316,
      "name": "kexec_image_post_load_cleanup_default",
      "external": false,
      "loc": "kernel/kexec_file.c:81",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:arch_kimage_file_post_load_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580173717,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:80",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:arch_kimage_file_post_load_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173664,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580219685,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:78",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:arch_kimage_file_post_load_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219632,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580268037,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:78",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:arch_kimage_file_post_load_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267984,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580337653,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:78",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:arch_kimage_file_post_load_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580337600,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580322869,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:79",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:arch_kimage_file_post_load_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580322816,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580326373,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:79",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:arch_kimage_file_post_load_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580326320,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580480901,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:79",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:arch_kimage_file_post_load_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580480848,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580675200,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:76",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kimage_file_post_load_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675200,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580945952,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:79",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kimage_file_post_load_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945952,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581032864,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:79",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kimage_file_post_load_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581032864,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581131072,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:79",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kimage_file_post_load_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581131072,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491510816,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:78",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:arch_kimage_file_post_load_cleanup"
      ],
      "caller_func": [
        "arch/arm64/kernel/machine_kexec_file.c:arch_kimage_file_post_load_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491510712,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284473408,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:78",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:arch_kimage_file_post_load_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284473280,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580236837,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:78",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:arch_kimage_file_post_load_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580236784,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580184389,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:78",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:arch_kimage_file_post_load_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184336,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580228309,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:78",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:arch_kimage_file_post_load_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580228256,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```

```json
{
  "name": "kexec_image_post_load_cleanup_default",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580281077,
      "name": "kexec_image_post_load_cleanup_default",
      "external": true,
      "loc": "kernel/kexec_file.c:78",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:arch_kimage_file_post_load_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580281024,
      "name": "kexec_image_post_load_cleanup_default",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage * image)
```
</details>
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
