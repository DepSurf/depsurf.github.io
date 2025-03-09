# Function: <code>round_pipe_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581032478,
      "name": "round_pipe_size",
      "external": false,
      "loc": "fs/pipe.c:1050",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_proc_fn",
        "fs/pipe.c:pipe_fcntl"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581191995,
      "name": "round_pipe_size",
      "external": false,
      "loc": "fs/pipe.c:1068",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:pipe_proc_fn"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581269148,
      "name": "round_pipe_size",
      "external": false,
      "loc": "fs/pipe.c:1023",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:pipe_proc_fn"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581318142,
      "name": "round_pipe_size",
      "external": false,
      "loc": "fs/pipe.c:1022",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:pipe_proc_fn"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int round_pipe_size(unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581458144,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1028",
      "file": "fs/pipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458144,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581617950,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1033",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612608,
      "name": "round_pipe_size.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581617744,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581704174,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1026",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698960,
      "name": "round_pipe_size.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581703968,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581822076,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1038",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581816592,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581821872,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581894636,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1038",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581889152,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581894432,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582124624,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1216",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582116848,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582124048,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582170496,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1216",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170496,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582195136,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1230",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582195136,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582512479,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1233",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592229450,
      "name": "round_pipe_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071582512448,
      "name": "round_pipe_size",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583031899,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1234",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:do_proc_dopipe_max_size_conv"
      ],
      "caller_func": [
        "fs/pipe.c:do_proc_dopipe_max_size_conv",
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583029488,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071594009107,
      "name": "round_pipe_size.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071594009179,
      "name": "round_pipe_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071583036992,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583596203,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1234",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:do_proc_dopipe_max_size_conv"
      ],
      "caller_func": [
        "fs/pipe.c:do_proc_dopipe_max_size_conv",
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583593728,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071596050461,
      "name": "round_pipe_size.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071596050533,
      "name": "round_pipe_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071583601680,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583813003,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1239",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:do_proc_dopipe_max_size_conv"
      ],
      "caller_func": [
        "fs/pipe.c:do_proc_dopipe_max_size_conv",
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583810320,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071596572952,
      "name": "round_pipe_size.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071596573024,
      "name": "round_pipe_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071583818560,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
unsigned int round_pipe_size(unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584019005,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1255",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:do_proc_dopipe_max_size_conv"
      ],
      "caller_func": [
        "fs/pipe.c:do_proc_dopipe_max_size_conv",
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016448,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071597477460,
      "name": "round_pipe_size.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071597477533,
      "name": "round_pipe_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071584024512,
      "name": "round_pipe_size",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493373544,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1038",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493366024,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336493373216,
      "name": "round_pipe_size",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226960156,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1038",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226954152,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 3226959916,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286921456,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1038",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286913008,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 13835058055286921136,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273091862,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1038",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273087028,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446743936273091626,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581863372,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1038",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581857888,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581863168,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581800972,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1038",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795488,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581800768,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581854684,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1038",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581849200,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581854480,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int round_pipe_size(long unsigned int size)
```

```json
{
  "name": "round_pipe_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581924172,
      "name": "round_pipe_size",
      "external": true,
      "loc": "fs/pipe.c:1038",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl"
      ],
      "caller_func": [
        "fs/pipe.c:pipe_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918704,
      "name": "round_pipe_size.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581923968,
      "name": "round_pipe_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
unsigned int round_pipe_size(unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int size</code> ➡️ <code>long unsigned int size</code>
</li>
</ul>
</details>
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
<b>Param type changed. </b>
<code>long unsigned int size</code> ➡️ <code>unsigned int size</code>
</li>
</ul>
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
