# .github/actions/build/Dockerfile
FROM rust:latest

RUN cargo install mdbook --no-default-features --features output --vers "^0.1.0"

CMD ["mdbook", "build"]
