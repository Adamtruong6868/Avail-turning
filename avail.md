### 2. Hardware required
**This is the hardware configuration required to set up an Avail validator node:**

**Step 1: Update system**
```php
sudo apt update && sudo apt upgrade -y
```

**Step 2: Install packages**
```php
sudo apt install make clang pkg-config libssl-dev build-essential git screen protobuf-compiler -y
```

**Step 3: Install Rust**
```php
curl https://sh.rustup.rs -sSf | sh
```

**Select 1 and enter**

**Step 4: Go to home**
```php
source $HOME/.cargo/env
```

**Step 5: Update rust**
```php
rustup update nightly
```

**Step 6: Add tools**
```php
rustup target add wasm32-unknown-unknown --toolchain nightly
```
