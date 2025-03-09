# Function: <code>do_one_pass</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595151847,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:65",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581907088,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:420",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907088,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3536
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595323946,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:65",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582094240,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:419",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094240,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595572131,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:65",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582184336,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:419",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582184336,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596499825,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:65",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582270496,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:419",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270496,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2996
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602827231,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582419648,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:419",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419648,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2996
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603000640,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:416",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582610160,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2484
    },
    {
      "addr": 18446744071582613247,
      "name": "do_one_pass.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604799458,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:416",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582711840,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2572
    },
    {
      "addr": 18446744071582715007,
      "name": "do_one_pass.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604902753,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:416",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582885312,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2580
    },
    {
      "addr": 18446744071582888486,
      "name": "do_one_pass.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604936712,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:416",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582991888,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2580
    },
    {
      "addr": 18446744071582995062,
      "name": "do_one_pass.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609250793,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memtest.c:early_memtest"
      ]
    },
    {
      "addr": 0,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:416",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609250793,
      "name": "do_one_pass",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 425
    },
    {
      "addr": 18446744071583308768,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2031
    },
    {
      "addr": 18446744071583311393,
      "name": "do_one_pass.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612317077,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memtest.c:early_memtest"
      ]
    },
    {
      "addr": 0,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:456",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612317077,
      "name": "do_one_pass",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 425
    },
    {
      "addr": 18446744071583424000,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2360
    },
    {
      "addr": 18446744071591349676,
      "name": "do_one_pass.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614457334,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memtest.c:early_memtest"
      ]
    },
    {
      "addr": 0,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:455",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614457334,
      "name": "do_one_pass",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071583446176,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2879
    },
    {
      "addr": 18446744071591292497,
      "name": "do_one_pass.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615402123,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memtest.c:early_memtest"
      ]
    },
    {
      "addr": 0,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:455",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615402123,
      "name": "do_one_pass",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071583795744,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2963
    },
    {
      "addr": 18446744071592273557,
      "name": "do_one_pass.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617194106,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memtest.c:early_memtest"
      ]
    },
    {
      "addr": 0,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:455",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617194106,
      "name": "do_one_pass",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071584359888,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3216
    },
    {
      "addr": 18446744071594055496,
      "name": "do_one_pass.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627892266,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585010432,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:461",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585010432,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3539
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619655098,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:72",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585238000,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:467",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585238000,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3650
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621960234,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:73",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585471344,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:466",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585471344,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3524
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510976448,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494677880,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:416",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494677880,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2920
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243457888,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 3228117584,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:416",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228117584,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302633392,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288491840,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:416",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288491840,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270700928,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274036064,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:416",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274036064,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2988
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604842172,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:416",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582960624,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2580
    },
    {
      "addr": 18446744071582963798,
      "name": "do_one_pass.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604811233,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:416",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582897776,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2580
    },
    {
      "addr": 18446744071582900950,
      "name": "do_one_pass.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604919356,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:416",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949232,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2580
    },
    {
      "addr": 18446744071582952406,
      "name": "do_one_pass.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "do_one_pass",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604940883,
      "name": "do_one_pass",
      "external": false,
      "loc": "mm/memtest.c:66",
      "file": "mm/memtest.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "do_one_pass",
      "external": false,
      "loc": "fs/jbd2/recovery.c:416",
      "file": "fs/jbd2/recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:jbd2_journal_skip_recovery",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover",
        "fs/jbd2/recovery.c:jbd2_journal_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583037616,
      "name": "do_one_pass",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2617
    },
    {
      "addr": 18446744071583040822,
      "name": "do_one_pass.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
