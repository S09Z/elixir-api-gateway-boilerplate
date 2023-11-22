FROM elixir:latest
WORKDIR /app
COPY . .
RUN mix do deps.get, compile
CMD ["mix", "phx.server"]