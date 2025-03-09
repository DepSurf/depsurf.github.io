# Function: <code>process_measurement</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int process_measurement(struct file * file, int mask, int function, int opened)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582610240,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:157",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_module_check",
        "security/integrity/ima/ima_main.c:ima_fw_from_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582610240,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1145
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
int process_measurement(struct file * file, char * buf, loff_t size, int mask, enum ima_hooks func, int opened)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582856080,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:157",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582856080,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1443
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
int process_measurement(struct file * file, char * buf, loff_t size, int mask, enum ima_hooks func, int opened)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582952688,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:158",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952688,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1680
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
int process_measurement(struct file * file, char * buf, loff_t size, int mask, enum ima_hooks func, int opened)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002656,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:158",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002656,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1686
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
int process_measurement(struct file * file, char * buf, loff_t size, int mask, enum ima_hooks func, int opened)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166784,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:162",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166784,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1670
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
int process_measurement(struct file * file, const struct cred * cred, u32 secid, char * buf, loff_t size, int mask, enum ima_hooks func, int opened)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583371920,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:169",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583371920,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2378
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
int process_measurement(struct file * file, const struct cred * cred, u32 secid, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583490688,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:171",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583490688,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2337
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
int process_measurement(struct file * file, const struct cred * cred, u32 secid, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583677248,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:192",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583677248,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2676
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
int process_measurement(struct file * file, const struct cred * cred, u32 secid, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583783952,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:192",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583783952,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2849
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
int process_measurement(struct file * file, const struct cred * cred, struct lsmblob * blob, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584175008,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:190",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584175008,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2580
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
int process_measurement(struct file * file, const struct cred * cred, struct lsmblob * blob, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584293872,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:196",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293872,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2717
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
int process_measurement(struct file * file, const struct cred * cred, struct lsmblob * blob, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584327792,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:196",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584327792,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2739
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
int process_measurement(struct file * file, const struct cred * cred, struct lsmblob * blob, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:201",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715280,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2932
    },
    {
      "addr": 18446744071592308121,
      "name": "process_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int process_measurement(struct file * file, const struct cred * cred, struct lsmblob * blob, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:201",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585390096,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2914
    },
    {
      "addr": 18446744071594090441,
      "name": "process_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int process_measurement(struct file * file, const struct cred * cred, struct lsmblob * blob, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:201",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586142752,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3000
    },
    {
      "addr": 18446744071596102304,
      "name": "process_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int process_measurement(struct file * file, const struct cred * cred, struct lsmblob * blob, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:206",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586380864,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3022
    },
    {
      "addr": 18446744071596625438,
      "name": "process_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int process_measurement(struct file * file, const struct cred * cred, struct lsmblob * blob, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:207",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586645456,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3295
    },
    {
      "addr": 18446744071597531064,
      "name": "process_measurement.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int process_measurement(struct file * file, const struct cred * cred, u32 secid, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495587576,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:192",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495587576,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2032
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
int process_measurement(struct file * file, const struct cred * cred, u32 secid, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228948368,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:192",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228948368,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2152
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
int process_measurement(struct file * file, const struct cred * cred, u32 secid, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289687440,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:192",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289687440,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2904
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
int process_measurement(struct file * file, const struct cred * cred, u32 secid, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274752442,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:192",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274752442,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1708
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
int process_measurement(struct file * file, const struct cred * cred, u32 secid, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583752688,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:192",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583752688,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2849
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
int process_measurement(struct file * file, const struct cred * cred, u32 secid, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583689744,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:192",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583689744,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2849
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
int process_measurement(struct file * file, const struct cred * cred, u32 secid, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583736464,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:192",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583736464,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2849
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
int process_measurement(struct file * file, const struct cred * cred, u32 secid, char * buf, loff_t size, int mask, enum ima_hooks func)
```

```json
{
  "name": "process_measurement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583837392,
      "name": "process_measurement",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:192",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583837392,
      "name": "process_measurement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2849
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * buf</code>
</li>
<li>
<b>Param added. </b>
<code>loff_t size</code>
</li>
<li>
<b>Param added. </b>
<code>enum ima_hooks func</code>
</li>
<li>
<b>Param removed. </b>
<code>int function</code>
</li>
<li>
<b>Param reordered. </b>
<code>file, mask, function, opened</code> ➡️ <code>file, buf, size, mask, func, opened</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred * cred</code>
</li>
<li>
<b>Param added. </b>
<code>u32 secid</code>
</li>
<li>
<b>Param reordered. </b>
<code>file, buf, size, mask, func, opened</code> ➡️ <code>file, cred, secid, buf, size, mask, func, opened</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int opened</code>
</li>
</ul>
</details>
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
<code>struct lsmblob * blob</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 secid</code>
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
