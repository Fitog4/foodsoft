web: bundle exec rdbg -n --open --nonstop --host 0.0.0.0 --port 12345 --open=0.0.0.0:12345 -- bin/rails server --binding=0.0.0.0 --port=$PORT -e development
worker: QUEUE=* bundle exec rake resque:work
mail: bundle exec rake foodsoft:reply_email_smtp_server
cron: supercronic crontab
