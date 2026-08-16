FROM caddy:2-alpine
COPY . /usr/share/caddy
EXPOSE 80
CMD ["sh", "-c", "caddy file-server --root /usr/share/caddy --listen :${PORT:-80}"]
