# Function: <code>__send_ipi_mask</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579024432,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:130",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579024432,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 727
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579028480,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:134",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ]
    },
    {
      "addr": 18446744071579314464,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:450",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_all",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579028480,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    },
    {
      "addr": 18446744071579314464,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579036496,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:139",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ]
    },
    {
      "addr": 18446744071579330448,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:434",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_all",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579036496,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071579330448,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579038816,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:139",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ]
    },
    {
      "addr": 18446744071579334688,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:434",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038816,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071579334688,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579048352,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:139",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579364112,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:458",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048352,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071579364112,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579051680,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:139",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579363136,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:479",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579051680,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071579363136,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579056880,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:141",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579368448,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:477",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056880,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    },
    {
      "addr": 18446744071579368448,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
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
bool __send_ipi_mask(const struct cpumask * mask, int vector, bool exclude_self)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579078320,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:155",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    },
    {
      "addr": 0,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:480",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078320,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
    },
    {
      "addr": 18446744071579429344,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 670
    },
    {
      "addr": 18446744071592079488,
      "name": "__send_ipi_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
bool __send_ipi_mask(const struct cpumask * mask, int vector, bool exclude_self)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579106432,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:155",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    },
    {
      "addr": 0,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:501",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106432,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
    },
    {
      "addr": 18446744071579497616,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
    },
    {
      "addr": 18446744071593846730,
      "name": "__send_ipi_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector, bool exclude_self)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143120,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:155",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    },
    {
      "addr": 0,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:500",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143120,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    },
    {
      "addr": 18446744071579593984,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 803
    },
    {
      "addr": 18446744071595967518,
      "name": "__send_ipi_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector, bool exclude_self)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143728,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:157",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    },
    {
      "addr": 0,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:500",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143728,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    },
    {
      "addr": 18446744071579606688,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 803
    },
    {
      "addr": 18446744071596485108,
      "name": "__send_ipi_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector, bool exclude_self)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579173024,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:157",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    },
    {
      "addr": 0,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:501",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579173024,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    },
    {
      "addr": 18446744071579636320,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
    },
    {
      "addr": 18446744071597381720,
      "name": "__send_ipi_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579039168,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:139",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ]
    },
    {
      "addr": 18446744071579330592,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:434",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579039168,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071579330592,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578971200,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:139",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ]
    },
    {
      "addr": 18446744071579265056,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:434",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578971200,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
    },
    {
      "addr": 18446744071579265056,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579038752,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:139",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ]
    },
    {
      "addr": 18446744071579330512,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:434",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038752,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071579330512,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__send_ipi_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579042400,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:139",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one"
      ]
    },
    {
      "addr": 18446744071579339056,
      "name": "__send_ipi_mask",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:434",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579042400,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071579339056,
      "name": "__send_ipi_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool exclude_self</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool __send_ipi_mask(const struct cpumask * mask, int vector)
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
