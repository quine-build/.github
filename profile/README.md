# Quine

Quine is the verifiable compiler compiler.

We are building a reproducible, transparent and self-verifying toolchain for
trusted software development – starting from zero, without relying on opaque
infrastructure or unverifiable assumptions.

The name "Quine" refers not only to the well-known self-replicating program, but
also stands for: **Quine is not evil**.

## Why

In 1984, Ken Thompson warned the world: you cannot trust software you didn't
build entirely yourself. But most of today's systems depend on compilers,
firmware, and toolchains that cannot be fully audited – let alone verified.

We believe this is no longer acceptable.

## What

Quine is a research project to design and implement a verifiable foundation for
compiler infrastructure. Our goal is to create a minimal, inspectable compiler
that can be bootstrapped from first principles and executed on open hardware.

Quine does not rely on any existing operating system, BIOS or standard
development stack. Instead, it targets bare metal environments such as
RISC-V, AArch64, or even SUBLEQ. We work towards end-to-end verifiability using
techniques like structured provenance, SHAKE256 hashing, and physical
inspection via JTAG or logic analysers.

## Who

Quine is developed as part of a doctoral research project. It is driven by the
need for secure, verifiable, and reproducible software systems – in a world
where trust must be earned, not assumed.

If you are interested in trustworthy computing, open hardware, compiler design,
or formal verification, you are very welcome to follow along, contribute, or
discuss.

More information at [https://quine.build](https://quine.build)
