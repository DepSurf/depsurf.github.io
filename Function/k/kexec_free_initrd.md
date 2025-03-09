# Function: <code>kexec_free_initrd</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604650749,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:537",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:populate_rootfs"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604663021,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:537",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:populate_rootfs"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool kexec_free_initrd()
```

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609014177,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:545",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:populate_rootfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609014177,
      "name": "kexec_free_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 123
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
bool kexec_free_initrd()
```

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612076201,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:552",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:populate_rootfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612076201,
      "name": "kexec_free_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614214886,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:617",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_populate_rootfs"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615133678,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:618",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_populate_rootfs"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616896340,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:643",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_populate_rootfs"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627489951,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:643",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_populate_rootfs"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619234011,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:636",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_populate_rootfs"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621524120,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:646",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_populate_rootfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510813504,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:537",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:populate_rootfs"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243259488,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:537",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:populate_rootfs"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302378232,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:537",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:populate_rootfs"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:560",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604589293,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:537",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:populate_rootfs"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604580970,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:537",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:populate_rootfs"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604667117,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:537",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:populate_rootfs"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_free_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604667122,
      "name": "kexec_free_initrd",
      "external": false,
      "loc": "init/initramfs.c:537",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:populate_rootfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool kexec_free_initrd()
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool kexec_free_initrd()
```
</details>
</li>
</ul>
