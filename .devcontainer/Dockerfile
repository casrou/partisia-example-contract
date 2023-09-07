FROM rust:1.72

# Update default packages
# RUN apt-get update

# Get Ubuntu packages
# RUN apt-get install -y \
#     build-essential \
#     curl

# Update new packages
# RUN apt-get update

# Get Rust
# RUN curl https://sh.rustup.rs -sSf | bash -s -- -y

# ENV PATH="/root/.cargo/bin:${PATH}"

# RUN rustup install 1.70
# RUN rustup default 1.70

RUN rustup target add wasm32-unknown-unknown

RUN cargo install cargo-partisia-contract
