# Function: <code>__ext4_abort</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581698288,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:571",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698288,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581890432,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:600",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890432,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581979632,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:602",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581979632,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582195824,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:619",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582195824,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582344544,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:618",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:ext4_journal_check_start",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344544,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:624",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:ext4_journal_check_start",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562991,
      "name": "__ext4_abort.cold.138",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582533776,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:666",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:ext4_journal_check_start",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582664207,
      "name": "__ext4_abort.cold.142",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582634864,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:677",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:ext4_journal_check_start",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836727,
      "name": "__ext4_abort.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582807456,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:672",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940854,
      "name": "__ext4_abort.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582910816,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, int error, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:707",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:ext4_journal_check_start",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583254909,
      "name": "__ext4_abort.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071583225584,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494587056,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:672",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494587056,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228029744,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:672",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228029744,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288386048,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:672",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:ext4_journal_check_start",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288386048,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273965724,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:672",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273965724,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:672",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582909590,
      "name": "__ext4_abort.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582879552,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:672",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846742,
      "name": "__ext4_abort.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582816704,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:672",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582898198,
      "name": "__ext4_abort.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582868432,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_abort",
      "external": true,
      "loc": "fs/ext4/super.c:672",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582985282,
      "name": "__ext4_abort.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582955136,
      "name": "__ext4_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
<code>int error</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, function, line, fmt, (anon)</code> ➡️ <code>sb, function, line, error, fmt, (anon)</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void __ext4_abort(struct super_block * sb, const char * function, unsigned int line, int error, const char * fmt, void (anon))
```
</details>
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
