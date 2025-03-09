# Function: <code>firmware_request_builtin</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool firmware_request_builtin(struct firmware * fw, const char * name)
```

```json
{
  "name": "firmware_request_builtin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588944533,
      "name": "firmware_request_builtin",
      "external": true,
      "loc": "drivers/base/firmware_loader/builtin/main.c:47",
      "file": "drivers/base/firmware_loader/builtin/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf",
        "drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588944384,
      "name": "firmware_request_builtin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool firmware_request_builtin(struct firmware * fw, const char * name)
```

```json
{
  "name": "firmware_request_builtin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590459653,
      "name": "firmware_request_builtin",
      "external": true,
      "loc": "drivers/base/firmware_loader/builtin/main.c:47",
      "file": "drivers/base/firmware_loader/builtin/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf",
        "drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590459488,
      "name": "firmware_request_builtin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool firmware_request_builtin(struct firmware * fw, const char * name)
```

```json
{
  "name": "firmware_request_builtin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590782517,
      "name": "firmware_request_builtin",
      "external": true,
      "loc": "drivers/base/firmware_loader/builtin/main.c:47",
      "file": "drivers/base/firmware_loader/builtin/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf",
        "drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:find_blobs_in_containers",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590782352,
      "name": "firmware_request_builtin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool firmware_request_builtin(struct firmware * fw, const char * name)
```

```json
{
  "name": "firmware_request_builtin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591125317,
      "name": "firmware_request_builtin",
      "external": true,
      "loc": "drivers/base/firmware_loader/builtin/main.c:47",
      "file": "drivers/base/firmware_loader/builtin/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf",
        "drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:get_microcode_blob",
        "arch/x86/kernel/cpu/microcode/amd.c:find_blobs_in_containers",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591125152,
      "name": "firmware_request_builtin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
bool firmware_request_builtin(struct firmware * fw, const char * name)
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
