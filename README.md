### Zen Blocks

Quick development environment for creating gutenberg blocks using Docker and create-guten-block.

I've also created some gutenberg blocks in this project.

## Dev Environment

Spinning up the dev environment is easy. Just run these steps on first run:

1. `docker-compose up --build -d` This will spin up a daemonized docker container with wordpress on it. Wait for awhile then head to `http://localhost:8080`.

2. On first run. You will be asked to setup your wordpress installation. Just proceed as usual.

3. Login wordpress admin with your newly created admin account. Go to plugins and you will already see your gutenberg blocks plugin there.

4. Run `npm install` then `npm start` on `plugins/zen-blocks` to continously watch for changes in the source code. This will build your updated block and reflect it immediately on your wordpress instance.
