# WebPagetest Docker Compose
Docker Compose files for private WebPagetest instance.

## Usage

### Startup the WebPagetest server and agent

#### On Mac OS

**Mac OS does not support network shaping within a Docker container however you can use [Throttle](https://github.com/sitespeedio/throttle).**

Run the following command, and access http://localhost:4000 in browser

```bash
docker-compose up -d
```

### Installation Check

Access http://localhost:4000/install in browser
If your agent is able to communicate with your server, you should see an agent connected for the Test Location

### Test Results

Test results are saved in `volumes/wpt_data` directory.

## License

[MIT](LICENSE)
