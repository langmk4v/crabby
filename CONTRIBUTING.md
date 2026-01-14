# Contributing to Crabby

Welcome to the Contributing Guidelines for Crabby!
Here, you can learn how to contribute to the `development` of Crabby.

## How Crabby is Build

Crabby is built in **Rust**, using crates like `logos`, `clap`, and more. Rust memory safety and
security, not to mention its *speed*, is appropriate to build languages like **Crabby**.

You also need to make sure to have the Rust **nightly toolchain** installed, if not yet you can run:

```bash
rustup toolchain install nightly
```

Then make it **default**:

```bash
rustup default nightly
```

## How to Contribute to Crabby?

We welcome a wide variety of contributions. Here's how you can get started:

> [!IMPORTANT]
> It is highly recommended to use the `dev` branch for mainly developing and testing crabby, as the `main` branch is only for stable or for a fixed released.

### 1. Fork Crabby

Start by [forking the repository](https://github.com/crabby-lang/crabby/fork) to your own GitHub account.

### 2. Clone Crabby

Clone your `fork` locally so you can begin making changes.

```bash
git clone https://github.com/crabby-lang/crabby.git
cd crabby
```

### 3. Create a New Branch

For each new feature, bug fix, or improvement, create a separate branch to keep your changes organized.

```bash
git checkout -b dev/my-new-feature
```

### 4. Commit Your Changes

Make sure to test your changes thoroughly and follow the project's coding standards. Once ready, commit your changes.

```bash
git add .
git commit -m "Description of the changes"
```

### 5. Push to Your Fork and Submit a Pull Request

Push your changes to your forked repository and submit a pull request to the `dev` branch of Crabby.

```bash
git push origin dev/my-new-feature
```

### 6. Review Process

In Crabby, we review your changes or features carefully, making sure no **malicious** or **sneaky**
code is written to the language, it may take up to a couple of minutes to hours, or in some cases, days.

## What can I contribute?

You can **contribute** to Crabby🦀 by:

- Fixing bugs
- Adding new features (e.g Crabby's Syntax, Improvements, Optimization, the Interpreter/Compiler)
- Issuing a change of Crabby's syntax
- Library/Package making
- Expanding the documentation
- Testing & Benchmarking Crabby
