# Function: <code>_atomic_dec_and_lock_irqsave</code>

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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589126656,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126656,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589361344,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589361344,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589818432,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589818432,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590044704,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590044704,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585038656,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/keyslot-manager.c:blk_ksm_put_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585038656,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585190656,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/keyslot-manager.c:blk_ksm_put_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190656,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585073760,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/keyslot-manager.c:blk_ksm_put_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073760,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585520544,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:put_ucounts",
        "block/keyslot-manager.c:blk_ksm_put_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520544,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586673088,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:put_ucounts",
        "block/blk-crypto-profile.c:blk_crypto_put_keyslot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586673088,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595752288,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:put_ucounts",
        "block/blk-crypto-profile.c:blk_crypto_put_keyslot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595752288,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596276336,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:put_ucounts",
        "block/blk-crypto-profile.c:blk_crypto_put_keyslot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596276336,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597161024,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:put_ucounts",
        "block/blk-crypto-profile.c:blk_crypto_put_keyslot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597161024,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503805952,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503805952,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236428924,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236428924,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297645056,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297645056,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279702620,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279702620,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589646960,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589646960,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589372832,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372832,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590090336,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590090336,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "_atomic_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590140592,
      "name": "_atomic_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/dec_and_lock.c:37",
      "file": "lib/dec_and_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590140592,
      "name": "_atomic_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int _atomic_dec_and_lock_irqsave(atomic_t * atomic, spinlock_t * lock, long unsigned int * flags)
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
