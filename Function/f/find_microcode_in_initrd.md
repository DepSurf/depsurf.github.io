# Function: <code>find_microcode_in_initrd</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579169840,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:215",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579169840,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579169616,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:244",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579169616,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579184544,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:261",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579184544,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579196016,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:261",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196016,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579185424,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:261",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185424,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579198144,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:257",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198144,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579200368,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:257",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579200368,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221280,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:252",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221280,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579215728,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:250",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579215728,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579218192,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:250",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218192,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:250",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592067476,
      "name": "find_microcode_in_initrd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579256480,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:233",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593833747,
      "name": "find_microcode_in_initrd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071579307904,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:233",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595962247,
      "name": "find_microcode_in_initrd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071579373632,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:233",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:find_blobs_in_containers",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596479788,
      "name": "find_microcode_in_initrd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071579382976,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
struct cpio_data find_microcode_in_initrd(const char * path)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621665776,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:186",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:get_microcode_blob",
        "arch/x86/kernel/cpu/microcode/amd.c:find_blobs_in_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621665776,
      "name": "find_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 158
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579199216,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:257",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579199216,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579134208,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:257",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579134208,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579200288,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:257",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579200288,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```

```json
{
  "name": "find_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579205568,
      "name": "find_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:257",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205568,
      "name": "find_microcode_in_initrd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool use_pa</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cpio_data find_microcode_in_initrd(const char * path, bool use_pa)
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
