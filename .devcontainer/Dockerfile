FROM rust:1.72

RUN rustup target add wasm32-unknown-unknown

RUN cargo install cargo-partisia-contract

# Get Java 17
RUN apt-get update
RUN apt-get -y install openjdk-17-jdk openjdk-17-source openjdk-17-doc