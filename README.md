# Conformance Testing Binaries

This repository contains **prebuilt Vinwolf binaries** (`vinwolf-target`) used for conformance and fuzz testing of the JAM implementation.

These binaries are intended to be consumed by external conformance and fuzzing tools.

---

## Usage

The binaries are typically invoked as follows:

```bash
vinwolf-target --fuzz $DIR
```

Where `$DIR` points to the directory containing the test vectors or fuzzing inputs.

Tipical usage:

```bash
vinwolf-target --fuzz /tmp/jam_target.sock
```

---

## Platform support

Additional binaries for other operating systems or architectures may be added **on demand**, depending on testing requirements.

---
