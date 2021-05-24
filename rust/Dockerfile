FROM rust:1.40

WORKDIR /app


RUN cargo new hello --bin ; cd hello

ADD data /app/hello/



RUN cd hello; ls ; cargo build

CMD cd hello; cargo run
