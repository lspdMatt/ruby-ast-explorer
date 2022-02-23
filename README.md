how to start

```bash
docker compose up -d
bundle exec rails db:schema:load && bundle exec rails db:migrate
bundle exec puma -C config/puma.rb
```