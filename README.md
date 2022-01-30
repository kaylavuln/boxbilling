## Prerequisites and System Requirement

- Docker Desktop or Docker CLI with Docker Compose installed. Follow this [instructions](https://www.docker.com/get-started) to have Docker on your machine.
- Git installed. Follow this [instructions] https://github.com/git-guides/install-git

## Step by Step Installation

- Make a folder named `niagahoster-test` or whatever you want and run this command into folder inside:
```
	git clone https://github.com/kaylavuln/boxbilling
```
- Extract `docker-config.zip` to folder `boxbilling` after you clone this repo before
- Finally, run this command inside `boxbilling` command:
```
	docker compose up
```
- Wait a moment this is very slow :) on my machine, and let docker build images and containers.
- Once containers up and ready to go (http://localhost).
- And BoxBilling go to (http://localhost:8004).
- On Administrator tab fill in all fields, this is link go to (http://localhost:8004/bb-admin). For example, our installation values are:
```
    Email : admin@gmail.com
    Password : EAW5hEP9nr4Vn3H
```

## Side Notes

- I using Operationg System Windows 10 Pro (Not Windows Server)
- For images i using Alphine.
- Any question? please email me for more information.
