FROM rust:1-slim
COPY . .
RUN cargo build --release
ENTRYPOINT [ "./target/release/rust" ]