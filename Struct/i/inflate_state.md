# Struct: <code>inflate_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
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
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
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
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct inflate_state {
    inflate_mode mode;
    int last;
    int wrap;
    int havedict;
    int flags;
    unsigned int dmax;
    long unsigned int check;
    long unsigned int total;
    unsigned int wbits;
    unsigned int wsize;
    unsigned int whave;
    unsigned int write;
    unsigned char * window;
    long unsigned int hold;
    unsigned int bits;
    unsigned int length;
    unsigned int offset;
    unsigned int extra;
    const code * lencode;
    const code * distcode;
    unsigned int lenbits;
    unsigned int distbits;
    unsigned int ncode;
    unsigned int nlen;
    unsigned int ndist;
    unsigned int have;
    code * next;
    short unsigned int[320] lens;
    short unsigned int[288] work;
    code[2048] codes;
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
