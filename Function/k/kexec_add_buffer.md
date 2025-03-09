# Function: <code>kexec_add_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kexec_add_buffer(struct kimage * image, char * buffer, long unsigned int bufsz, long unsigned int memsz, long unsigned int buf_align, long unsigned int buf_min, long unsigned int buf_max, bool top_down, long unsigned int * load_addr)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953392,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:482",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953392,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
int kexec_add_buffer(struct kimage * image, char * buffer, long unsigned int bufsz, long unsigned int memsz, long unsigned int buf_align, long unsigned int buf_min, long unsigned int buf_max, bool top_down, long unsigned int * load_addr)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579983760,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:435",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983760,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580014400,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:483",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014400,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580021568,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:484",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021568,
      "name": "kexec_add_buffer",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580068576,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:486",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068576,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580127408,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:552",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127408,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580174720,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:610",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580174720,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:656",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580225396,
      "name": "kexec_add_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580220800,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580269072,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:661",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269072,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580339008,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:648",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_purgatory_setup_kbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580339008,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580324304,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:667",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_purgatory_setup_kbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580324304,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580327584,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:667",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580327584,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580482096,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:667",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580482096,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580676528,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:626",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580676528,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580947536,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:630",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580947536,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034528,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:633",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034528,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581132544,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:643",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132544,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491512392,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:661",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/machine_kexec_file.c:load_other_segments",
        "arch/arm64/kernel/machine_kexec_file.c:load_other_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491512392,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284473792,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:661",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/kexec_elf_64.c:elf64_load",
        "arch/powerpc/kernel/kexec_elf_64.c:elf64_load",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_elf.c:kexec_elf_load",
        "security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284473792,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580237872,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:661",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580237872,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580185424,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:661",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185424,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580229136,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:661",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580229136,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int kexec_add_buffer(struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_add_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580282112,
      "name": "kexec_add_buffer",
      "external": true,
      "loc": "kernel/kexec_file.c:661",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "arch/x86/kernel/kexec-bzimage64.c:bzImage64_load",
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282112,
      "name": "kexec_add_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kexec_buf * kbuf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kimage * image</code>
</li>
<li>
<b>Param removed. </b>
<code>char * buffer</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int bufsz</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int memsz</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int buf_align</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int buf_min</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int buf_max</code>
</li>
<li>
<b>Param removed. </b>
<code>bool top_down</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * load_addr</code>
</li>
</ul>
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
int kexec_add_buffer(struct kexec_buf * kbuf)
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
int kexec_add_buffer(struct kexec_buf * kbuf)
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
